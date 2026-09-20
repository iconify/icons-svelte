<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/b/bmu-7y.css';
import '../../css/l/l48m1g.css';
import '../../css/s/so-from-32.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c bmu-7y"/><path class="a0m25c l48m1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:github" {...props}></Icon>
