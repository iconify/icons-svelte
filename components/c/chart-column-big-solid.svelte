<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nin_08yup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nin_08yup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-column-big-solid" {...props}></Icon>
