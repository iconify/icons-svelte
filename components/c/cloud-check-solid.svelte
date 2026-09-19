<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdzs51bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gdzs51bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:cloud-check-solid" {...props}></Icon>
