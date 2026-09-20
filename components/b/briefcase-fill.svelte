<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxur0bc0h.css';
import '../../css/q/q114wtnjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxur0bc0h"/><path class="q114wtnjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:briefcase-fill" {...props}></Icon>
