<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1cnlywwj.css';
import '../../css/w/w0dn1zvis.css';
import '../../css/y/yu09v8bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1cnlywwj"/><path class="w0dn1zvis"/><path class="yu09v8bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:lock-shield-bold" {...props}></Icon>
