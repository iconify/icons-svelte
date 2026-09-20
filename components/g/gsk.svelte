<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlgrb4bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlgrb4bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gsk" {...props}></Icon>
