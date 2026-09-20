<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq53nzb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fq53nzb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:dash" {...props}></Icon>
