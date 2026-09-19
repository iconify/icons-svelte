<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fly7y8bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fly7y8bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:lifebuoy-solid" {...props}></Icon>
