<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu-0ao1so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qu-0ao1so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:battery-low-fill" {...props}></Icon>
