<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eya_kzb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eya_kzb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bike-sharp" {...props}></Icon>
