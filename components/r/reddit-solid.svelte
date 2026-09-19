<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_7nqnbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o_7nqnbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:reddit-solid" {...props}></Icon>
