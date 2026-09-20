<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o553x7pes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o553x7pes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:laravel-logo-2-solid" {...props}></Icon>
