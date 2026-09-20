<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n07rvdbgg.css';
import '../../css/i/iigxsq-iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n07rvdbgg"/><path class="iigxsq-iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:go" {...props}></Icon>
