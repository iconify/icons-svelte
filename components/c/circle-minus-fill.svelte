<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhku4kbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lhku4kbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-minus-fill" {...props}></Icon>
