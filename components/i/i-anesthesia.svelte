<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqaqbm0ih.css';
import '../../css/t/tsm0aygxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="hqaqbm0ih"/><path class="tsm0aygxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-anesthesia" {...props}></Icon>
