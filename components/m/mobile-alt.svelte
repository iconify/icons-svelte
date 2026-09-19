<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8bxn6b7q.css';
import '../../css/m/mojfvmkcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8bxn6b7q"/><circle class="mojfvmkcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:mobile-alt" {...props}></Icon>
