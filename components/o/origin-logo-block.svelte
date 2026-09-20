<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-nvybc7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-nvybc7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:origin-logo-block" {...props}></Icon>
