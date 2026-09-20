<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8na7v9av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-7};
const content = `<path class="m8na7v9av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:align-center" {...props}></Icon>
