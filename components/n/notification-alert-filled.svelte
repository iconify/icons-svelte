<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/polv4dizi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="polv4dizi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:notification-alert-filled" {...props}></Icon>
