<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc7aclrmb.css';
import '../../css/f/f4xb95eqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc7aclrmb"/><path clip-rule="evenodd" class="f4xb95eqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-unlock-fill" {...props}></Icon>
