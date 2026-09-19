<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcpu1rbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hcpu1rbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:person-magnifier" {...props}></Icon>
