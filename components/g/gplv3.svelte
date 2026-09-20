<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkit6zbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkit6zbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gplv3" {...props}></Icon>
