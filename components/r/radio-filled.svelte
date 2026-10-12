<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebt6dfb6z.css';
import '../../css/m/mpz6u0b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebt6dfb6z"/><path class="mpz6u0b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:radio-filled" {...props}></Icon>
