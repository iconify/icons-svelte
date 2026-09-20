<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmpzh7bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kmpzh7bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:blackberry-logo-block" {...props}></Icon>
