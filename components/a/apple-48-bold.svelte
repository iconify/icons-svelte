<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq9rmtbnw.css';
import '../../css/g/g77nglpfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gq9rmtbnw"/><path class="g77nglpfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:apple-48-bold" {...props}></Icon>
