<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3mjm7bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3mjm7bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-left-square-line" {...props}></Icon>
