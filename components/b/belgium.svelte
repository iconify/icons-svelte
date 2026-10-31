<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_nhc2bkw.css';
import '../../css/w/wnghrmbmj.css';
import '../../css/c/cp7tt2bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="k_nhc2bkw"/><path class="wnghrmbmj"/><path class="cp7tt2bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:belgium" {...props}></Icon>
