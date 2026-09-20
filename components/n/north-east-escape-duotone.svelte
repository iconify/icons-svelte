<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts8p5pbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ts8p5pbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:north-east-escape-duotone" {...props}></Icon>
