<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmw8ecbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmw8ecbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:projects-fill" {...props}></Icon>
