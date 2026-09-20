<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-tedebsj.css';
import '../../css/t/tp-8ulbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="m-tedebsj"/><path class="tp-8ulbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-no-smoking" {...props}></Icon>
