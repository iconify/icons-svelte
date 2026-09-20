<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5n0-rb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5n0-rb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:keep" {...props}></Icon>
