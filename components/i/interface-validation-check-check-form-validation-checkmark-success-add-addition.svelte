<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmco-5kri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rmco-5kri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-validation-check-check-form-validation-checkmark-success-add-addition" {...props}></Icon>
