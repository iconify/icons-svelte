<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pztpj7b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pztpj7b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:git-pull-solid" {...props}></Icon>
