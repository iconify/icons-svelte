<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl-5a4gok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gl-5a4gok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clock-square-outline" {...props}></Icon>
