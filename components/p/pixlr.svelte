<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpz0cj0fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpz0cj0fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pixlr" {...props}></Icon>
