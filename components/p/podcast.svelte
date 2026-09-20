<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/r-gsambcb.css';
import '../../css/q/qnn9vyb6a.css';
import '../../css/a/aej6_67ns.css';
import '../../css/c/c7gfsbb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r-gsambcb"/><path class="qnn9vyb6a"/><path class="aej6_67ns"/><circle class="c7gfsbb7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:podcast" {...props}></Icon>
