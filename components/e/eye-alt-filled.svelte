<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymz-vs81r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymz-vs81r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:eye-alt-filled" {...props}></Icon>
