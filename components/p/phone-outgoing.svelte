<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v42ex0_-k.css';
import '../../css/e/epcgjnb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v42ex0_-k"/><path class="epcgjnb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-outgoing" {...props}></Icon>
