<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-a_st0ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-a_st0ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:compress" {...props}></Icon>
