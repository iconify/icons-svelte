<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sobe6ub7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sobe6ub7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gift-card-02" {...props}></Icon>
