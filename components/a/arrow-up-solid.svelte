<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohewd5--p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohewd5--p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-up-solid" {...props}></Icon>
