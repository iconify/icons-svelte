<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr2er1f5h.css';
import '../../css/z/z6ezkobko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr2er1f5h"/><path class="z6ezkobko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-checkbox-filled" {...props}></Icon>
