<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sifkdq4hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sifkdq4hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:camera-fill" {...props}></Icon>
