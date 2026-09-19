<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9mo31emm.css';
import '../../css/y/ysrry-bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9mo31emm"/><path class="ysrry-bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-up-right-circle" {...props}></Icon>
