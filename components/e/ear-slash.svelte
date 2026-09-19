<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqo2otbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqo2otbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ear-slash" {...props}></Icon>
