<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf6hw5b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nf6hw5b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-six-small" {...props}></Icon>
