<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnolt0wrb.css';
import '../../css/q/q6oeacb7k.css';
import '../../css/l/lflficb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnolt0wrb"/><path class="q6oeacb7k"/><path class="lflficb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:article-duotone" {...props}></Icon>
