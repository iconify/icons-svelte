<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnaft7gra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnaft7gra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:flag-fill" {...props}></Icon>
