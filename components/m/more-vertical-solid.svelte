<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu-2ao_sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu-2ao_sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:more-vertical-solid" {...props}></Icon>
