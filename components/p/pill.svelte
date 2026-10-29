<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji5e_cc1a.css';
import '../../css/h/h1ei_9byu.css';
import '../../css/k/kh6xzbb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji5e_cc1a"/><path class="h1ei_9byu"/><path class="kh6xzbb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:pill" {...props}></Icon>
