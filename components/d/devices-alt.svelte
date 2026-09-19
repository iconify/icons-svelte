<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csjodqbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="csjodqbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:devices-alt" {...props}></Icon>
