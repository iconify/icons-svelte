<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/n/n_g2ks.css';
import '../../css/j/j5x9vw.css';
import '../../css/z/z28l-c.css';
import '../../css/t/tv0bue.css';
import '../../css/s/so-from-16.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c n_g2ks"/><path class="a0m25c j5x9vw"/><path class="a0m25c z28l-c"/><path class="a0m25c tv0bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:align-left" {...props}></Icon>
