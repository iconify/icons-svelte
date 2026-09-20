<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2jr2o6cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2jr2o6cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:id-card-sharp" {...props}></Icon>
