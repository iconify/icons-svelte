<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnjos3bch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnjos3bch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:props" {...props}></Icon>
