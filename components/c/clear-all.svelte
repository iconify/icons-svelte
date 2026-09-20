<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5ftfqbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o5ftfqbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:clear-all" {...props}></Icon>
