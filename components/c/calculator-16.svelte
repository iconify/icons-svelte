<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sieez-brj.css';
import '../../css/v/v4lyffbho.css';
import '../../css/x/x7_vrbb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sieez-brj"/><path class="v4lyffbho"/><path clip-rule="evenodd" class="x7_vrbb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:calculator-16" {...props}></Icon>
