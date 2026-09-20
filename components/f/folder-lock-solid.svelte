<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1qmh6bea.css';
import '../../css/k/k52lm57aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1qmh6bea"/><path clip-rule="evenodd" class="k52lm57aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-lock-solid" {...props}></Icon>
