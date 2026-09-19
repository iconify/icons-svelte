<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3bhk4bbt.css';
import '../../css/f/fuc7qlr2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3bhk4bbt"/><path class="fuc7qlr2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-jpg" {...props}></Icon>
