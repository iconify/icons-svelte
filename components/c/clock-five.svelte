<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cep2c0bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cep2c0bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:clock-five" {...props}></Icon>
