<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqe91nbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rqe91nbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-quarter-fill" {...props}></Icon>
