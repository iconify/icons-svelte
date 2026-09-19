<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_agz1bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l_agz1bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:bootstrap-fill" {...props}></Icon>
