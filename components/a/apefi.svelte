<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkl0h0b7k.css';
import '../../css/c/c29sjqb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkl0h0b7k"/><path class="c29sjqb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:apefi" {...props}></Icon>
