<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh0s8cc3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jh0s8cc3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:deliciousing-logo-solid" {...props}></Icon>
