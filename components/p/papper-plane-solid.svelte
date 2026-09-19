<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyeo0eqpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oyeo0eqpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:papper-plane-solid" {...props}></Icon>
