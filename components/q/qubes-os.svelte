<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_-ut4buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_-ut4buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qubes-os" {...props}></Icon>
