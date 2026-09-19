<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbw59hkqr.css';
import '../../css/u/u19mxjbnb.css';
import '../../css/k/k16fi-_we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbw59hkqr"/><path class="u19mxjbnb"/><path class="k16fi-_we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:image-alt" {...props}></Icon>
