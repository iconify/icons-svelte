<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnoop7bqe.css';
import '../../css/h/h_ao2xbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnoop7bqe"/><path class="h_ao2xbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:american-football-helmet-bold" {...props}></Icon>
