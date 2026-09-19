<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnerglbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fnerglbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:check-badge-solid" {...props}></Icon>
