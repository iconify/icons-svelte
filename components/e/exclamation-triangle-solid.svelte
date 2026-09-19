<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obz4z6kng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="obz4z6kng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:exclamation-triangle-solid" {...props}></Icon>
