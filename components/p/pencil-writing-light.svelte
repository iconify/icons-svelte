<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohmadlugj.css';
import '../../css/h/h89cyrqhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohmadlugj"/><path class="h89cyrqhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pencil-writing-light" {...props}></Icon>
