<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so9k2acpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="so9k2acpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:circle-f" {...props}></Icon>
