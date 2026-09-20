<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl-rk3sls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl-rk3sls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:knip" {...props}></Icon>
