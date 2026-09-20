<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr6lwtbkj.css';
import '../../css/y/ymdjnobca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="nr6lwtbkj"/><path class="ymdjnobca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:no-smoking" {...props}></Icon>
