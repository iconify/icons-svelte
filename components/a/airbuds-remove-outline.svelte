<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu0k8wbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qu0k8wbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-remove-outline" {...props}></Icon>
