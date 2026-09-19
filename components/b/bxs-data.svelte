<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sebzf9cjk.css';
import '../../css/u/ujddx7bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sebzf9cjk"/><path class="ujddx7bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-data" {...props}></Icon>
