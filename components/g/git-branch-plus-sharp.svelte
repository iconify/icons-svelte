<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q07upcb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q07upcb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-branch-plus-sharp" {...props}></Icon>
