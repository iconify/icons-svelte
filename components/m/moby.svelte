<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkw7-jbie.css';
import '../../css/n/nvnedvrpl.css';
import '../../css/r/r75br4b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkw7-jbie"/><path class="nvnedvrpl"/><path class="r75br4b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:moby" {...props}></Icon>
