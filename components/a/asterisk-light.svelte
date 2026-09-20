<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipu4fx39x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipu4fx39x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:asterisk-light" {...props}></Icon>
