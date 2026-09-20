<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lawae4buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lawae4buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:osmc-logo-block" {...props}></Icon>
