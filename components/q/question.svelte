<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/j/jz878g.css';
import '../../css/n/nj20st.css';
import '../../css/s/so-from-30.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c jz878g"/><path class="a0m25c nj20st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:question" {...props}></Icon>
