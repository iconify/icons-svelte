<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzdh5gb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzdh5gb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calculator-solid" {...props}></Icon>
