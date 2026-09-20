<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-9-kkb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-9-kkb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:diigo-logo-3-block" {...props}></Icon>
