<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7cdzdb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7cdzdb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:asterisk-solid" {...props}></Icon>
