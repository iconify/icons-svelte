<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-5qlccsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-5qlccsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:leaf-fill-round" {...props}></Icon>
