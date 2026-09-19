<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfe39lxep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lfe39lxep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-hebrew-small" {...props}></Icon>
