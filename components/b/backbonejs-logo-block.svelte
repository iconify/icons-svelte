<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw_z6bmih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw_z6bmih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:backbonejs-logo-block" {...props}></Icon>
