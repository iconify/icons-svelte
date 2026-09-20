<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihnb7ebwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihnb7ebwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-bolt" {...props}></Icon>
