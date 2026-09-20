<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrfh4bqnd.css';
import '../../css/f/fpe9bqb4y.css';
import '../../css/q/qcqglrpgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<rect class="wrfh4bqnd"/><path class="fpe9bqb4y"/><circle class="qcqglrpgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nubjs" {...props}></Icon>
