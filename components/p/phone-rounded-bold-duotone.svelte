<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag883ssbj.css';
import '../../css/q/qumoqc5xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ag883ssbj"/><path class="qumoqc5xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-rounded-bold-duotone" {...props}></Icon>
