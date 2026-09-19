<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nikrg4bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nikrg4bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-vertical-justify-center" {...props}></Icon>
