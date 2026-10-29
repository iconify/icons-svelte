<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9gsl6b1j.css';
import '../../css/v/vb6su3tol.css';
import '../../css/k/k1xtew5eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9gsl6b1j"/><path class="vb6su3tol"/><path class="k1xtew5eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:database" {...props}></Icon>
