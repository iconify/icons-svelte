<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8goj0b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8goj0b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:black-forest-labs-bfl" {...props}></Icon>
