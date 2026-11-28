<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqx9jqbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary rqx9jqbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:health-cross-duotone" {...props}></Icon>
