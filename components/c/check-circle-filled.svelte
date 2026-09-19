<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfk5y9bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfk5y9bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:check-circle-filled" {...props}></Icon>
