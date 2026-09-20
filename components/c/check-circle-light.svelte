<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z--u7bblr.css';
import '../../css/i/ivxllx4mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z--u7bblr"/><path class="ivxllx4mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:check-circle-light" {...props}></Icon>
