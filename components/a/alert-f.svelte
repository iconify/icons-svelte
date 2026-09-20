<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzy6ww4uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="tzy6ww4uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:alert-f" {...props}></Icon>
