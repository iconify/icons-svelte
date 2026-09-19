<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dohg0wbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dohg0wbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:rain" {...props}></Icon>
