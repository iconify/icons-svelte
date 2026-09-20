<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcv3qbcsb.css';
import '../../css/z/zq4712bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":269.567,"height":153.532};
const content = `<path class="kcv3qbcsb"/><path class="zq4712bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:amazon-fire-tv" {...props}></Icon>
