<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs749jbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bs749jbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:conditioner-2-outline" {...props}></Icon>
