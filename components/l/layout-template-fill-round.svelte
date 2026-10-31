<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pheg_6bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pheg_6bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:layout-template-fill-round" {...props}></Icon>
