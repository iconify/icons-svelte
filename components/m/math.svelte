<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-lrl4bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m-lrl4bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:math" {...props}></Icon>
