<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-3cpv8jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-3cpv8jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:backbonejs-logo-solid" {...props}></Icon>
