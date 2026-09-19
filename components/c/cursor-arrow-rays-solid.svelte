<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh4k8abwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eh4k8abwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cursor-arrow-rays-solid" {...props}></Icon>
